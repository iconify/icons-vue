<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am1tq7v-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am1tq7v-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-letter-g-filled" /></template>
