<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvy_q-q5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvy_q-q5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:circle-three-quarter-alt-filled" /></template>
