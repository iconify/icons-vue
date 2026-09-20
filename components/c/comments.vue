<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w576l3brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w576l3brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comments" /></template>
