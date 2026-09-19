<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgb1ac0gi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dgb1ac0gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-up-right-square-solid" /></template>
