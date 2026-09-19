<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uczo_kpja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uczo_kpja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:fisker" /></template>
