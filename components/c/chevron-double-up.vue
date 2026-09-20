<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-akw3bix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-akw3bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chevron-double-up" /></template>
