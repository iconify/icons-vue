<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my5e902_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my5e902_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrows-expand-right-alt" /></template>
