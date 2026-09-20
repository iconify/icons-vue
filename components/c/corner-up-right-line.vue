<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzsx7yoyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzsx7yoyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:corner-up-right-line" /></template>
