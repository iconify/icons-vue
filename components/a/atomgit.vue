<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq7_43b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq7_43b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:atomgit" /></template>
