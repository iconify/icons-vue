<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmpd__bdx.css';
import '../../css/a/a30rl-bmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b fmpd__bdx"/><path class="a30rl-bmq b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:computer" /></template>
