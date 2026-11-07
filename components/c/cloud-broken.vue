<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp93toeom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp93toeom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-broken" /></template>
