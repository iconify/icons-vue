<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmt358bze.css';
import '../../css/d/dre6y_9-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hmt358bze"/><path class="dre6y_9-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:diskette-bold" /></template>
