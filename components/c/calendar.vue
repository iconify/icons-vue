<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk-ljkbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":650,"height":679};
const content = `<path class="nk-ljkbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:calendar" /></template>
