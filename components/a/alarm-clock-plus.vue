<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfao_98jr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfao_98jr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:alarm-clock-plus" /></template>
