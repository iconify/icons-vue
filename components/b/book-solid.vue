<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp2f8wozq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp2f8wozq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:book-solid" /></template>
