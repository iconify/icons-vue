<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqei2rb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oqei2rb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:crown-20-solid" /></template>
