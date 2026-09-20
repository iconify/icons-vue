<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtv06358b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtv06358b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-right-short-fill" /></template>
