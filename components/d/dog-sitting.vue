<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxqyoy7th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nxqyoy7th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dog-sitting" /></template>
