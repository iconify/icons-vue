<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr2a8d89r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr2a8d89r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-older-woman-gloss" /></template>
