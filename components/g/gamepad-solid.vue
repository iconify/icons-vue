<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr2iu8bhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hr2iu8bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:gamepad-solid" /></template>
