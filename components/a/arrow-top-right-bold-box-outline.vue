<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkw6s9bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkw6s9bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-top-right-bold-box-outline" /></template>
