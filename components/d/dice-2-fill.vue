<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya_2pob1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya_2pob1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dice-2-fill" /></template>
