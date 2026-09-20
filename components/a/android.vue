<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gay2lcc4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<path class="gay2lcc4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:android" /></template>
