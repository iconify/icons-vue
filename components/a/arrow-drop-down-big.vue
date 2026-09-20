<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue_62kavg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue_62kavg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:arrow-drop-down-big" /></template>
