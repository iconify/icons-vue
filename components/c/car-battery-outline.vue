<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgbg3kb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dgbg3kb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:car-battery-outline" /></template>
