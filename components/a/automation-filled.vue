<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knyvgjvpz.css';
import '../../css/f/fbz-pkkzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knyvgjvpz"/><path class="fbz-pkkzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:automation-filled" /></template>
