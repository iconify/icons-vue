<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx9-o-b0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx9-o-b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:asterisk-simple" /></template>
