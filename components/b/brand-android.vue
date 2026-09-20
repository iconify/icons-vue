<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9z5yabwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9z5yabwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-android" /></template>
