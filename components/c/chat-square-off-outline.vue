<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2j0411cb.css';
import '../../css/r/rormt7btc.css';
import '../../css/n/nn1-acc4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2j0411cb"/><path class="rormt7btc"/><path class="nn1-acc4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-off-outline" /></template>
