<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5nm9bbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5nm9bbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:archive" /></template>
