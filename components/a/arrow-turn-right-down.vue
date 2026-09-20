<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5u6iac2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5u6iac2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrow-turn-right-down" /></template>
