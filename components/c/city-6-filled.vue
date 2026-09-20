<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q74bkpbtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q74bkpbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:city-6-filled" /></template>
