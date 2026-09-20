<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoco9ob4a.css';
import '../../css/s/sa1x33xzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xoco9ob4a"/><path class="sa1x33xzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:hospital-circle-fill" /></template>
