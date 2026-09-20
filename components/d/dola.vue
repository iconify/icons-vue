<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf70dbbds.css';
import '../../css/r/rwk1vccqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sf70dbbds"/><path class="rwk1vccqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dola" /></template>
