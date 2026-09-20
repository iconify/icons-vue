<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqbx91-km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqbx91-km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:box-align-right" /></template>
