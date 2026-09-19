<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5bsa5vjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5bsa5vjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:inbox-arrow-down" /></template>
