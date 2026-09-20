<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc97uuhut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc97uuhut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:crown-outline" /></template>
