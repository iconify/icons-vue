<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6_rr2b4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="d6_rr2b4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:iphone" /></template>
