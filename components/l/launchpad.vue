<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgc_kyikd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgc_kyikd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:launchpad" /></template>
