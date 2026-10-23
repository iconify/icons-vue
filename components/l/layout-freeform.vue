<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njo54y4mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njo54y4mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:layout-freeform" /></template>
