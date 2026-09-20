<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o38ht4b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o38ht4b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:flag-2-fill" /></template>
