<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl4kxw-7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bl4kxw-7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:magnifying-glass" /></template>
