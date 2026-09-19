<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzr7qwbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzr7qwbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:bell-off" /></template>
