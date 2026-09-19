<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czzfe_76l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":24};
const content = `<path class="czzfe_76l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:grunt" /></template>
