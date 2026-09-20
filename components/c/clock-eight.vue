<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgja8vbbk.css';
import '../../css/i/ixpwojbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgja8vbbk"/><path class="ixpwojbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:clock-eight" /></template>
