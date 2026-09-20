<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjd8obcdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xjd8obcdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:airport" /></template>
