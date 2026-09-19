<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9-nxbkyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="p9-nxbkyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:lock-shield-fill" /></template>
