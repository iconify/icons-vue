<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n185p7bwm.css';
import '../../css/i/iylza4btn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n185p7bwm"/><path class="iylza4btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:chevrons-down" /></template>
