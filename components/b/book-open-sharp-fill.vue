<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya-k_gblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya-k_gblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:book-open-sharp-fill" /></template>
