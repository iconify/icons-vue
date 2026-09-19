<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn2us-vvy.css';
import '../../css/y/y-9gdnm7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn2us-vvy"/><path class="y-9gdnm7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:broadcast" /></template>
