<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqk85vbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cqk85vbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hard-hat" /></template>
