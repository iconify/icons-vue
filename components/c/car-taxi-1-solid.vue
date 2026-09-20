<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm9nwob-m.css';
import '../../css/h/hnglj9b8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rm9nwob-m"/><path clip-rule="evenodd" class="hnglj9b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:car-taxi-1-solid" /></template>
