<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6f5j_qip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path class="z6f5j_qip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cobol" /></template>
