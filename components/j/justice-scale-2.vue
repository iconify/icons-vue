<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bunby8b1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="bunby8b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:justice-scale-2" /></template>
