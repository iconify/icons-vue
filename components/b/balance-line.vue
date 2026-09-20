<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho2uy5bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho2uy5bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:balance-line" /></template>
