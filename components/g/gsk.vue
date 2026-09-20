<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlgrb4bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlgrb4bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gsk" /></template>
