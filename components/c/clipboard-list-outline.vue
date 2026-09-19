<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh1e9m4lr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh1e9m4lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:clipboard-list-outline" /></template>
