<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6go8hb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="x6go8hb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:blackboard" /></template>
