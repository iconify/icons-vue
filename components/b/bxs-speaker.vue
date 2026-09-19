<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz9ucbcni.css';
import '../../css/j/j6-b0layc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="wz9ucbcni"/><path class="j6-b0layc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-speaker" /></template>
