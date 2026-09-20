<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzp8_ubtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzp8_ubtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:dna-strand" /></template>
