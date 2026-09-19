<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqv4dg9_v.css';
import '../../css/g/gxt-rhbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqv4dg9_v"/><path class="gxt-rhbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:credit-card-off" /></template>
