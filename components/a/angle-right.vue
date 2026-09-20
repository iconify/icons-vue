<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_rpn8b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_rpn8b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:angle-right" /></template>
