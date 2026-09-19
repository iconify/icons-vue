<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h94enslwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h94enslwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:lock-alt-01-filled" /></template>
