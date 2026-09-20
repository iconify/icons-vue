<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivymxac-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivymxac-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:expand-left-double-light" /></template>
