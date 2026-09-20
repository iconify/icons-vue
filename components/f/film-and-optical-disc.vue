<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he1c9nb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="he1c9nb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:film-and-optical-disc" /></template>
