<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzy02n6it.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzy02n6it"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:gem" /></template>
