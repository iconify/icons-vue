<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ana4hn6qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ana4hn6qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-credit-card-outline" /></template>
