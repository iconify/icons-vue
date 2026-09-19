<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afafpebrx.css';
import '../../css/s/sv58jibeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afafpebrx"/><path class="sv58jibeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:doughnut-chart-filled" /></template>
