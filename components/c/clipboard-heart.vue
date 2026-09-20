<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2aqyxblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q2aqyxblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:clipboard-heart" /></template>
