<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvlfp99rn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvlfp99rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dna-fill" /></template>
