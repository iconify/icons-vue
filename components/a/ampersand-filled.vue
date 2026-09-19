<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwjuhxzbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b rwjuhxzbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ampersand-filled" /></template>
