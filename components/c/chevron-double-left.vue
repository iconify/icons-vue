<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu5qzcslb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu5qzcslb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:chevron-double-left" /></template>
