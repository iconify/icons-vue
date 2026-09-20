<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nitixhb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nitixhb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:edit-solid" /></template>
