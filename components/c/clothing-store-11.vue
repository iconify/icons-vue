<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl_kitb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="pl_kitb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:clothing-store-11" /></template>
