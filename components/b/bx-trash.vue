<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq_ak0bad.css';
import '../../css/v/v03ymlbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq_ak0bad"/><path class="v03ymlbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-trash" /></template>
