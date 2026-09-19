<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtfcq9iub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="jtfcq9iub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:file-new" /></template>
