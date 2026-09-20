<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vosp1ja8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vosp1ja8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:close-square-fill" /></template>
