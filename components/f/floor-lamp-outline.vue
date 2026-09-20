<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmn1gik9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmn1gik9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:floor-lamp-outline" /></template>
