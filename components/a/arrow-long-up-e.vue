<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5_l4yboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i5_l4yboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrow-long-up-e" /></template>
