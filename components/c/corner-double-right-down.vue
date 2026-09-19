<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlcle3b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlcle3b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:corner-double-right-down" /></template>
