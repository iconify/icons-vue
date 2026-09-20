<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr9mfq_-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr9mfq_-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:battery-low-fill" /></template>
