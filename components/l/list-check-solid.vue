<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j79n9n5fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j79n9n5fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:list-check-solid" /></template>
