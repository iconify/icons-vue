<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_8fwfbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="b_8fwfbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:css" /></template>
