<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkxnn-bnx.css';
import '../../css/v/vrxehybcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkxnn-bnx"/><path class="vrxehybcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:envelope-letter-front" /></template>
