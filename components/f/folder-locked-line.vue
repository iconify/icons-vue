<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/relhjsb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="relhjsb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-locked-line" /></template>
