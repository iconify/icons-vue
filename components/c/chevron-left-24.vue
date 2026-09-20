<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kszekzz1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kszekzz1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:chevron-left-24" /></template>
