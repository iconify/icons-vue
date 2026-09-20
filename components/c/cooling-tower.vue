<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly7k85m8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ly7k85m8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:cooling-tower" /></template>
