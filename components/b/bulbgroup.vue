<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj6uqbcna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj6uqbcna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulbgroup" /></template>
