<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6w97ub9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6w97ub9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:cloud-drizzle" /></template>
