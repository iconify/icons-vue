<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1w31db5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c1w31db5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bed-solid" /></template>
