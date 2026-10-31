<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxq6zy91w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxq6zy91w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:keyboard-gloss" /></template>
