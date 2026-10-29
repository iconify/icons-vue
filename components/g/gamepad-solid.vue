<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn0jcekjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn0jcekjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gamepad-solid" /></template>
