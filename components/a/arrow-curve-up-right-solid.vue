<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6v1yabvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c6v1yabvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-up-right-solid" /></template>
