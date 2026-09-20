<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or80zd0ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="or80zd0ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:camera-add2-filled" /></template>
