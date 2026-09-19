<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvk3j3elz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvk3j3elz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:book-edit" /></template>
