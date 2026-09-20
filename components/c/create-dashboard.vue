<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb-o2tbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb-o2tbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:create-dashboard" /></template>
