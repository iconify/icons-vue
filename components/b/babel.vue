<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2pb5bbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2pb5bbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:babel" /></template>
