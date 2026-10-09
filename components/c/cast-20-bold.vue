<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7g4iqb1i.css';
import '../../css/m/mwlvaabdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b7g4iqb1i"/><path class="mwlvaabdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cast-20-bold" /></template>
