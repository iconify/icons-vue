<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzjrmyb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzjrmyb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:id-card-x" /></template>
