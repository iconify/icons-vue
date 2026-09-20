<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx4mcabwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wx4mcabwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:loader-2" /></template>
