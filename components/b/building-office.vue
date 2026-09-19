<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xovzl2klm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xovzl2klm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:building-office" /></template>
