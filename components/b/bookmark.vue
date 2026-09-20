<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc67n3bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc67n3bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:bookmark" /></template>
