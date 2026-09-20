<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twzjjvbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twzjjvbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:broadcast-fill" /></template>
