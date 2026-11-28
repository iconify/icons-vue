<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grs1shbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grs1shbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:magnet-solid" /></template>
