<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxh3hib-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxh3hib-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bigcommerce" /></template>
