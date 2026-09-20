<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adt168bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adt168bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flag-variant-minus-outline" /></template>
