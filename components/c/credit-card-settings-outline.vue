<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikf92o_9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikf92o_9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-settings-outline" /></template>
