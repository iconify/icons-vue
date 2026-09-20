<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd8l7tbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd8l7tbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bigbasket" /></template>
