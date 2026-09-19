<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byqtji88p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="byqtji88p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:elec" /></template>
