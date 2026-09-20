<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtvtce9_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mtvtce9_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:chevron-left-12" /></template>
