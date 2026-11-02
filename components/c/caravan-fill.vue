<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqbw_ebrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqbw_ebrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:caravan-fill" /></template>
