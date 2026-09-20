<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4-404nwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4-404nwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:content-save-all-outline" /></template>
