<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phb40rbgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phb40rbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber-color:arrange-letter" /></template>
