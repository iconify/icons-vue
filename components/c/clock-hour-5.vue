<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teagswbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="teagswbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clock-hour-5" /></template>
