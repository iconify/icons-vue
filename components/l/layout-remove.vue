<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd153t_sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wd153t_sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:layout-remove" /></template>
