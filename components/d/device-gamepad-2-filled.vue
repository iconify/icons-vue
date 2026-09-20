<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7uxqcifs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7uxqcifs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-gamepad-2-filled" /></template>
