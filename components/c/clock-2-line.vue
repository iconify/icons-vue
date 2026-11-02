<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_6ut2b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_6ut2b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-2-line" /></template>
