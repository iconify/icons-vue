<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmrph42ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jmrph42ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:briefcase-filled" /></template>
