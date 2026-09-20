<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbvone-jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbvone-jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hitachi" /></template>
