<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc1oq6b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oc1oq6b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:info-circle" /></template>
