<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6idjfb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6idjfb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:button-rounded" /></template>
