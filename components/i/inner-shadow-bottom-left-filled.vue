<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo5_o1bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo5_o1bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:inner-shadow-bottom-left-filled" /></template>
