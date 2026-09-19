<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmh6un4qk.css';
import '../../css/i/iaergbsgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mmh6un4qk"/><path class="iaergbsgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:door" /></template>
