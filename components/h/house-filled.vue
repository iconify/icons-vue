<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh0_um3lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jh0_um3lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:house-filled" /></template>
