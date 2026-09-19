<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3yr3sb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="c3yr3sb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:flask-vial" /></template>
