<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/schfpoh5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="schfpoh5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cooldown-line" /></template>
