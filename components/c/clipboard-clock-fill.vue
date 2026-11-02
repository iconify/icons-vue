<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugjmlib4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugjmlib4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clipboard-clock-fill" /></template>
