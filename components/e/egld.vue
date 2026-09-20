<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnxu-q_7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnxu-q_7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:egld" /></template>
