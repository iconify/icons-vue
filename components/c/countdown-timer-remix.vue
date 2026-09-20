<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw6ug9bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nw6ug9bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:countdown-timer-remix" /></template>
