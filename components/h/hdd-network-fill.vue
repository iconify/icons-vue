<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av81snbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="av81snbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:hdd-network-fill" /></template>
