<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi9hynt1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi9hynt1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:diaper-outline" /></template>
