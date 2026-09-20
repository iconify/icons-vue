<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l966jgakv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l966jgakv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hand-heart-filled" /></template>
