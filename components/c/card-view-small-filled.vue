<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_g_psdmk.css';
import '../../css/j/ji90m8bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="r_g_psdmk"/><path class="ji90m8bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:card-view-small-filled" /></template>
