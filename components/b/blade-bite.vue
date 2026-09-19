<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9wdznbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x9wdznbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:blade-bite" /></template>
