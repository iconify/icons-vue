<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-69fabuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-69fabuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:eject" /></template>
