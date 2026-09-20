<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_zurloeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_zurloeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:dial-pad-bold" /></template>
