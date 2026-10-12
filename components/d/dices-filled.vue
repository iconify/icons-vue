<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh-_s4tzi.css';
import '../../css/f/fzny0updf.css';
import '../../css/r/rtlhf8blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nh-_s4tzi"/><path class="fzny0updf"/><path class="rtlhf8blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:dices-filled" /></template>
