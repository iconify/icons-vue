<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3l2b5bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="l3l2b5bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:adjustments-filled" /></template>
