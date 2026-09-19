<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzglvdb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fzglvdb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-down-circle-fill" /></template>
