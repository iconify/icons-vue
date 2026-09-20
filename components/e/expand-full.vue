<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abkecsx_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abkecsx_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:expand-full" /></template>
