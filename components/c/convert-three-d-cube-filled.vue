<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v87z958hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v87z958hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:convert-three-d-cube-filled" /></template>
