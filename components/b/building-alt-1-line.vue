<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5rnl5bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5rnl5bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:building-alt-1-line" /></template>
