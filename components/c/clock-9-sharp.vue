<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyxa7wbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyxa7wbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-9-sharp" /></template>
