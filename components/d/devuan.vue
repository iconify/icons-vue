<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph48qgb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ph48qgb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:devuan" /></template>
