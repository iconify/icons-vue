<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b25cx9bkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b25cx9bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:badge-percent-check" /></template>
