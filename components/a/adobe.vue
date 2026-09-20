<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9wg2obmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9wg2obmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:adobe" /></template>
