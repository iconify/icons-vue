<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt2ubuxgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt2ubuxgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-automotive-fill" /></template>
