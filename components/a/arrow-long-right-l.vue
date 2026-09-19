<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f23xl6srl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f23xl6srl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrow-long-right-l" /></template>
