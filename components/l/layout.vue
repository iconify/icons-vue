<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9eledb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9eledb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:layout" /></template>
