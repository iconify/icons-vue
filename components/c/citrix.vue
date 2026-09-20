<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntd1ge7ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntd1ge7ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:citrix" /></template>
