<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd2ockczu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="pd2ockczu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:desert-island" /></template>
