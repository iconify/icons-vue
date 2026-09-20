<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqy31ubzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqy31ubzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:less-than-or-equal" /></template>
