<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvygkcbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvygkcbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mail-question" /></template>
