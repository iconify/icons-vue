<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8hgrvbws.css';
import '../../css/q/qagm_33vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a8hgrvbws"/><path class="qagm_33vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bottles-container" /></template>
