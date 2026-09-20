<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzbidrbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzbidrbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:border-left" /></template>
