<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3jjhcb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o3jjhcb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:kaspersky" /></template>
