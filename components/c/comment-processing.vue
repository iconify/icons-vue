<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uayoccwof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uayoccwof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comment-processing" /></template>
