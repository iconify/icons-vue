<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkmw8b3ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkmw8b3ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:lightning-alt-light" /></template>
