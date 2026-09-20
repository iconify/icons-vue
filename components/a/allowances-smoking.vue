<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sibtb5ryj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sibtb5ryj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:allowances-smoking" /></template>
