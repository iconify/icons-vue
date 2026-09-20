<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud_d7qycl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud_d7qycl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:asus" /></template>
