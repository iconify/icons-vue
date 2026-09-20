<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg1qlmvrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg1qlmvrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:alibabadotcom" /></template>
