<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx9p37-xz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wx9p37-xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-horizontal-spark" /></template>
