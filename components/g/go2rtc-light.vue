<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt448_byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kt448_byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:go2rtc-light" /></template>
