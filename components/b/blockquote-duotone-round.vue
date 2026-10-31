<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyrdaub_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyrdaub_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:blockquote-duotone-round" /></template>
