<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5qp_zqit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e5qp_zqit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:circle-notch-solid" /></template>
