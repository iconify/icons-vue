<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrj2iywqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrj2iywqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:expand-down-light" /></template>
