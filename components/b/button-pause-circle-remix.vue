<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsbpq4b2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lsbpq4b2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:button-pause-circle-remix" /></template>
