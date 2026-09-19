<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2lg3s4-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v2lg3s4-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:folder" /></template>
