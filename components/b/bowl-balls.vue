<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp79jsbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp79jsbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bowl-balls" /></template>
