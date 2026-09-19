<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9oalu6-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9oalu6-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:happy-beaming" /></template>
