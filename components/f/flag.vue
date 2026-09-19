<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge7rpwnsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ge7rpwnsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:flag" /></template>
