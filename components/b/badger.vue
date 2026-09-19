<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waqhw0blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="waqhw0blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:badger" /></template>
