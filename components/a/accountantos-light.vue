<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt2iis1fl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1084,"height":1074};
const content = `<path class="kt2iis1fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:accountantos-light" /></template>
