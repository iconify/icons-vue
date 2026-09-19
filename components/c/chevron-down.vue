<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9ev0mbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9ev0mbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:chevron-down" /></template>
