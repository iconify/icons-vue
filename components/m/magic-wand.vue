<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tryux6b1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tryux6b1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:magic-wand" /></template>
