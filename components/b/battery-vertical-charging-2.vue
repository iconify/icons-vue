<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohqme2bkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohqme2bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-vertical-charging-2" /></template>
