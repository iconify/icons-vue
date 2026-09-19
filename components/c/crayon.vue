<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrojon6us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":1025};
const content = `<path class="hrojon6us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:crayon" /></template>
