<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xidz24b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xidz24b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:currency-pound" /></template>
