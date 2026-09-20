<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu4z57bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu4z57bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:co-op" /></template>
