<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drcgarb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="drcgarb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:add-user" /></template>
