<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auz6fkr2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-6.5,"top":-6.5};
const content = `<path class="auz6fkr2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:arrow-down-right" /></template>
