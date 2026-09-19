<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my-29jn8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my-29jn8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:list-checkmark" /></template>
