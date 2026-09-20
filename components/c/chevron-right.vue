<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4bdeub-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4bdeub-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:chevron-right" /></template>
