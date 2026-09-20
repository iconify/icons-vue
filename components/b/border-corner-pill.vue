<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_5j7i_8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_5j7i_8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:border-corner-pill" /></template>
