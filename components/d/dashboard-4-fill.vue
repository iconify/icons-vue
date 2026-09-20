<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asrrilb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asrrilb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dashboard-4-fill" /></template>
