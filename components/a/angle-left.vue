<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mro7kxbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mro7kxbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:angle-left" /></template>
