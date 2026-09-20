<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms5l_luvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms5l_luvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:forward-2-line" /></template>
