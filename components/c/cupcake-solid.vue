<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_2k7vlvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_2k7vlvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cupcake-solid" /></template>
