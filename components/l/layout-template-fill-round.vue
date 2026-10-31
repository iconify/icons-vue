<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pheg_6bdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pheg_6bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:layout-template-fill-round" /></template>
