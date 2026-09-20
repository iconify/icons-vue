<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_66kwbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_66kwbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heading-3" /></template>
