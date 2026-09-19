<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekry0bbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekry0bbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:flashlight-off" /></template>
