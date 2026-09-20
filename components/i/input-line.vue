<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fplwr48hg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fplwr48hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:input-line" /></template>
