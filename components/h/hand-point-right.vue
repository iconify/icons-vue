<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax7kk0bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ax7kk0bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:hand-point-right" /></template>
