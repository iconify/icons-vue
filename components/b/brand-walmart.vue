<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmg6x7buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmg6x7buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-walmart" /></template>
