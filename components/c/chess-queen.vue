<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmm7bu0st.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmm7bu0st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:chess-queen" /></template>
