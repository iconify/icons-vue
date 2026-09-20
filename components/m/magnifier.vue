<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl_h37b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl_h37b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:magnifier" /></template>
