<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s39tyujlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s39tyujlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:contract-left-fill" /></template>
