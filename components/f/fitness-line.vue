<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msj8-dbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msj8-dbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fitness-line" /></template>
