<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4bney4jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4bney4jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-arrow-down-sharp" /></template>
