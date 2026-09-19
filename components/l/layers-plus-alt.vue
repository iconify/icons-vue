<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piom46bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="piom46bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:layers-plus-alt" /></template>
