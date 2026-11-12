<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x__4p2bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x__4p2bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:asterism" /></template>
