<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx-ykwbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx-ykwbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:letter-p" /></template>
