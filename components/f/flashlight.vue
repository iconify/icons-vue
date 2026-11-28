<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8ob1qfny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8ob1qfny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:flashlight" /></template>
