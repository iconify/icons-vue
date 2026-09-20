<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx9mnmbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yx9mnmbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:document-link" /></template>
