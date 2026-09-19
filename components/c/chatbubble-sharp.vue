<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk3ypjbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fk3ypjbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:chatbubble-sharp" /></template>
