<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnzen6byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnzen6byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:cherry-filled" /></template>
