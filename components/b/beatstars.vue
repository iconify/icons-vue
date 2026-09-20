<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkx-7iotx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkx-7iotx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:beatstars" /></template>
