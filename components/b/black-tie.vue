<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yijhkhrdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="yijhkhrdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:black-tie" /></template>
