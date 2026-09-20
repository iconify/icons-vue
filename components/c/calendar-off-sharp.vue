<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uht88ogek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uht88ogek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-off-sharp" /></template>
