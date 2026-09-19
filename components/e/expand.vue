<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzf2fwb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzf2fwb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:expand" /></template>
