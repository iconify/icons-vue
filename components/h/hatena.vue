<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd7rvbbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":819,"height":681};
const content = `<path class="gd7rvbbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:hatena" /></template>
