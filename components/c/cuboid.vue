<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytoo606yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytoo606yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:cuboid" /></template>
