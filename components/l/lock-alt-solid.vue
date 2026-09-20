<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5_1xv7xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5_1xv7xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:lock-alt-solid" /></template>
