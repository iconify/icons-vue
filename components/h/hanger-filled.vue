<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmr98pfdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmr98pfdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:hanger-filled" /></template>
