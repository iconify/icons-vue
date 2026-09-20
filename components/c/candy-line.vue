<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh_sowbzl.css';
import '../../css/x/xxr0bwmsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh_sowbzl"/><path class="xxr0bwmsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:candy-line" /></template>
