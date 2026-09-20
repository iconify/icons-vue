<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj-m25pot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj-m25pot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lotion-plus" /></template>
