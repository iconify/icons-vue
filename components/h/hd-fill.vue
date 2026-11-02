<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgzaegbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgzaegbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hd-fill" /></template>
