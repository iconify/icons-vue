<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj4uocj8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj4uocj8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:battery" /></template>
