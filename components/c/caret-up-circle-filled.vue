<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a99y_q_qy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a99y_q_qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:caret-up-circle-filled" /></template>
