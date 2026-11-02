<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hafzs9bbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hafzs9bbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:color-picker-line" /></template>
