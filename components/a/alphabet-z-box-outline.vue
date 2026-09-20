<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfn9nbc2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfn9nbc2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-z-box-outline" /></template>
