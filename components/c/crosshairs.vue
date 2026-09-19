<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuocq_bke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuocq_bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:crosshairs" /></template>
