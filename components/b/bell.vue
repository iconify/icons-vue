<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izr86ab_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izr86ab_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bell" /></template>
