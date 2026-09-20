<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u38khkbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u38khkbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:adjust-brightness" /></template>
