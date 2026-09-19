<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emloct5vx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="emloct5vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:layout" /></template>
