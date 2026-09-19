<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0z2k8bik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g0z2k8bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:data-management-settings" /></template>
