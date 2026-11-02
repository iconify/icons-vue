<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vovp4rbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vovp4rbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lamp-floor-line" /></template>
