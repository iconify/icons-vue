<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iadv0h46r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iadv0h46r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:angle-down" /></template>
