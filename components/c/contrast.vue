<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqc3xdbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gqc3xdbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:contrast" /></template>
