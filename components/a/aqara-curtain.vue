<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkp_bd6ru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkp_bd6ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-curtain" /></template>
