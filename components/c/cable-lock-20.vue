<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2gsbjbrx.css';
import '../../css/k/kmot23zoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m2gsbjbrx"/><path class="kmot23zoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cable-lock-20" /></template>
