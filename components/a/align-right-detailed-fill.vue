<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1ryztnrd.css';
import '../../css/n/n6zdheb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1ryztnrd"/><path clip-rule="evenodd" class="n6zdheb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-right-detailed-fill" /></template>
