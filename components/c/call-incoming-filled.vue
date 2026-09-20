<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iruu2iqcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iruu2iqcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:call-incoming-filled" /></template>
