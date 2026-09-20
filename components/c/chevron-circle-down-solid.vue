<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahs9cdbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ahs9cdbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:chevron-circle-down-solid" /></template>
