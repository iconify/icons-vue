<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljkx69bul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljkx69bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:expand-down-double" /></template>
