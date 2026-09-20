<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehogni3ze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehogni3ze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:border-colour" /></template>
