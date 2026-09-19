<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvbix7bxx.css';
import '../../css/s/sldl10bkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvbix7bxx"/><path class="sldl10bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-down-right-stroke-square-filled" /></template>
