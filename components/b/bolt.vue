<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vghf96kzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vghf96kzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bolt" /></template>
