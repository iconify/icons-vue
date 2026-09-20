<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_ptm4baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="x_ptm4baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:key-security" /></template>
