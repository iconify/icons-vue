<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnxwasbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnxwasbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-ghost-gloss" /></template>
