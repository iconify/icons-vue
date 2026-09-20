<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbsc-5bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbsc-5bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:expand-left-stop" /></template>
