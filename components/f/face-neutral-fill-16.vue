<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de4e_zb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="de4e_zb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:face-neutral-fill-16" /></template>
