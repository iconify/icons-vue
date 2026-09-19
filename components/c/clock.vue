<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxpps5bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxpps5bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:clock" /></template>
