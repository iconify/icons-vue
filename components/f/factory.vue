<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_l_77bcd.css';
import '../../css/h/hbryolsnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_l_77bcd"/><path class="hbryolsnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:factory" /></template>
