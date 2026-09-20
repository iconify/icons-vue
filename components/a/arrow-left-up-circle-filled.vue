<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr83jrbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr83jrbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-left-up-circle-filled" /></template>
