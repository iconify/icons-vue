<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecc9xbbqc.css';
import '../../css/m/mmxphf4-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecc9xbbqc"/><path clip-rule="evenodd" class="mmxphf4-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:haze-fill" /></template>
