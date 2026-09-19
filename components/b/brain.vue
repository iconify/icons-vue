<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upe21snco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upe21snco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:brain" /></template>
