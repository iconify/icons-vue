<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxlfq5tuk.css';
import '../../css/l/leqoybczl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxlfq5tuk"/><path class="leqoybczl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-error-circle" /></template>
