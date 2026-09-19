<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jds0_5bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jds0_5bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:dice-2" /></template>
