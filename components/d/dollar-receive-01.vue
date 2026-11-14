<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wam2n5bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wam2n5bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dollar-receive-01" /></template>
