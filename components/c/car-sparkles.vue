<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5z6yebzw.css';
import '../../css/i/i9as8va8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5z6yebzw"/><path class="i9as8va8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:car-sparkles" /></template>
