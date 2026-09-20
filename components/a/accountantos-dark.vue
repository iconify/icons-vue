<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2cjcqnme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1084,"height":1074};
const content = `<path class="g2cjcqnme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:accountantos-dark" /></template>
