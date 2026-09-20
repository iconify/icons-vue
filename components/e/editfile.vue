<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-o2_ac3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="f-o2_ac3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:editfile" /></template>
