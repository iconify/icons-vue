<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moqx-40tt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="moqx-40tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:glass-filled" /></template>
