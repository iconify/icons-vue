<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stebkg-ap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stebkg-ap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comment-edit-outline" /></template>
