<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vun3xnubm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vun3xnubm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-arrow-from-top" /></template>
