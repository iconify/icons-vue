<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0iha821l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0iha821l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:letters-g" /></template>
