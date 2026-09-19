<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4uc9vb-s.css';
import '../../css/u/u7e-84bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":19,"height":24};
const content = `<path class="g4uc9vb-s"/><path class="u7e-84bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:hot-air-balloon" /></template>
