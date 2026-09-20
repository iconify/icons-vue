<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmwo-9w_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmwo-9w_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:archive-check" /></template>
