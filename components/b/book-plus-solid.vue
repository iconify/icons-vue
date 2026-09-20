<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm8bkbbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm8bkbbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:book-plus-solid" /></template>
