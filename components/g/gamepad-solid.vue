<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz2cu2yfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tz2cu2yfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:gamepad-solid" /></template>
