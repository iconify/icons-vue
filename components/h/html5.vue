<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_mofebcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y_mofebcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:html5" /></template>
