<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyvvhh_7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyvvhh_7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:game-2-line" /></template>
