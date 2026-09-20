<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqlvy8b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqlvy8b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-up-right-fill" /></template>
