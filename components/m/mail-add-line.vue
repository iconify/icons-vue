<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh5wkgpim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oh5wkgpim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mail-add-line" /></template>
