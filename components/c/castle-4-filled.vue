<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf3wfqbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf3wfqbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:castle-4-filled" /></template>
