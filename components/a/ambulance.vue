<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zavhcvy1d.css';
import '../../css/l/lwsmj8vpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":35,"height":24};
const content = `<path class="zavhcvy1d"/><path class="lwsmj8vpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:ambulance" /></template>
