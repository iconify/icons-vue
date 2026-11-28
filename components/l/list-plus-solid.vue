<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh2ohabkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh2ohabkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:list-plus-solid" /></template>
