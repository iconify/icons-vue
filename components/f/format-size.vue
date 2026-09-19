<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap4qq9qms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":384};
const content = `<path class="ap4qq9qms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-size" /></template>
