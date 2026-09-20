<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw5h_935k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jw5h_935k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gamepad-buttons-filled" /></template>
