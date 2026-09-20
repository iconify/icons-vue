<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_5sn5lkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_5sn5lkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clapperboard-settings-outline" /></template>
