<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1zey7w6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1zey7w6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:apt" /></template>
