<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8_3nubjg.css';
import '../../css/s/skvu_5_5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8_3nubjg"/><path class="skvu_5_5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:football" /></template>
