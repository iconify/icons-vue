<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3-oyth7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3-oyth7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:dimond-duotone" /></template>
