<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywk2o2cwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":528,"height":496};
const content = `<path class="ywk2o2cwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:do-not-wash" /></template>
