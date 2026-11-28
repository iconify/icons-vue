<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiwpa3b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oiwpa3b3b primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-right-duotone" /></template>
