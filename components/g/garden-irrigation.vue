<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8ue1pbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8ue1pbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:garden-irrigation" /></template>
