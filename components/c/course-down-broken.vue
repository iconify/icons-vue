<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpe-7kbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpe-7kbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:course-down-broken" /></template>
