<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr-qwf9jd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr-qwf9jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:briefcase-edit-outline" /></template>
