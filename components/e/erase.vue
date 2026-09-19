<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl17tqb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl17tqb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:erase" /></template>
