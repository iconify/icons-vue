<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz_2qjfda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz_2qjfda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:codeowners" /></template>
