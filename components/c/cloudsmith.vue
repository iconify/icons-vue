<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abetf7bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="abetf7bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cloudsmith" /></template>
