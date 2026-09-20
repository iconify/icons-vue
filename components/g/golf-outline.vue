<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic9ecqb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ic9ecqb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:golf-outline" /></template>
