<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx0jmzb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qx0jmzb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:devices-apps" /></template>
