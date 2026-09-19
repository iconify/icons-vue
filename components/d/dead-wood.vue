<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br43k87zk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="br43k87zk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dead-wood" /></template>
