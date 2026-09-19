<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqg3ftxno.css';
import '../../css/v/v6ayyo12g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqg3ftxno"/><path class="v6ayyo12g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-headphone" /></template>
