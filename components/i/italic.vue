<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zavzltd4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-7.5,"top":-7};
const content = `<path class="zavzltd4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:italic" /></template>
