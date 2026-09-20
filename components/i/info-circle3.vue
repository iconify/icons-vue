<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdek--bux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdek--bux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:info-circle3" /></template>
