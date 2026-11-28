<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwikjcbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwikjcbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-double-right-solid" /></template>
