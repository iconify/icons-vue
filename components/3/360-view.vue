<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czu4wbtlg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czu4wbtlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:360-view" /></template>
