<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gswvltbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gswvltbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:blogger-alt" /></template>
