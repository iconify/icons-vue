<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r08_g5bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r08_g5bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:computer" /></template>
