<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwi1r-0my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwi1r-0my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-navbar-inactive" /></template>
