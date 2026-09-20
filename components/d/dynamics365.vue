<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd-ht8b1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd-ht8b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:dynamics365" /></template>
