<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs_ds4bwb.css';
import '../../css/t/t1tvrdn3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bs_ds4bwb"/><path class="t1tvrdn3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:delivery-truck" /></template>
