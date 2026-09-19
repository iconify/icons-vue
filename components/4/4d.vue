<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo630cjbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zo630cjbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:4d" /></template>
