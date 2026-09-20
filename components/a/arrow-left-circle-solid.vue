<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_byhbb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="u_byhbb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-left-circle-solid" /></template>
