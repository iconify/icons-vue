<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufmuf6t2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufmuf6t2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:computer-desktop-slash" /></template>
