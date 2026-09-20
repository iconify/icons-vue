<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz2igeb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sz2igeb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:apache-hbase" /></template>
