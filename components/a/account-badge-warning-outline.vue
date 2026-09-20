<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lccrvp42b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lccrvp42b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-badge-warning-outline" /></template>
