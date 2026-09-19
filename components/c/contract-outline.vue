<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yml15xujg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yml15xujg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:contract-outline" /></template>
