<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6vjh8byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="i6vjh8byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:birthday" /></template>
