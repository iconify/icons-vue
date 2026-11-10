<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uum3rn3oq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uum3rn3oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:braces" /></template>
