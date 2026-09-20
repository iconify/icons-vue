<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alylnebpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alylnebpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:karlsruher-verkehrsverbund" /></template>
