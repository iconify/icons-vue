<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhj3tr_ac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhj3tr_ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:homify" /></template>
