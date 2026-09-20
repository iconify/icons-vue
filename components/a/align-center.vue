<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhjgo3bvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhjgo3bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:align-center" /></template>
