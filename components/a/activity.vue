<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyi1r0c8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyi1r0c8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:activity" /></template>
