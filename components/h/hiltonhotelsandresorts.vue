<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjmor_bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjmor_bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hiltonhotelsandresorts" /></template>
