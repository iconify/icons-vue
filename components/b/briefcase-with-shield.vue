<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm7kq5o3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sm7kq5o3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:briefcase-with-shield" /></template>
