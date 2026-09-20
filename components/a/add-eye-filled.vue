<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc2yc2txt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uc2yc2txt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:add-eye-filled" /></template>
