<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbl1qibzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sbl1qibzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:diff" /></template>
