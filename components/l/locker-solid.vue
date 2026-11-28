<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8p_jx3oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8p_jx3oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:locker-solid" /></template>
