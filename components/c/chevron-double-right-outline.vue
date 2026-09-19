<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l42_9wqpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l42_9wqpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:chevron-double-right-outline" /></template>
