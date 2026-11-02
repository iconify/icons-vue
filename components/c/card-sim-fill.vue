<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvm67acjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvm67acjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:card-sim-fill" /></template>
