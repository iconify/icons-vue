<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhkcgxb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="jhkcgxb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:chevron-left" /></template>
