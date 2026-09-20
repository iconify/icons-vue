<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxe6p1gov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1,"top":-2};
const content = `<path class="kxe6p1gov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:history" /></template>
