<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-a80lbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-a80lbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-sidebar-right-inactive" /></template>
