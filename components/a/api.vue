<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrlq88niw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrlq88niw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:api" /></template>
