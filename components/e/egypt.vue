<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta2xki0fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ta2xki0fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:egypt" /></template>
