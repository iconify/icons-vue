<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a39upxb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a39upxb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:alert-octagon" /></template>
