<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrxo5ibzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrxo5ibzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bbciplayer" /></template>
