<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8y5n6-du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8y5n6-du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:clapperboard-solid" /></template>
