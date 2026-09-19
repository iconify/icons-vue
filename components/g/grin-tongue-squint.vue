<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je1i2lqnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="je1i2lqnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:grin-tongue-squint" /></template>
