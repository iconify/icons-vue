<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5vt00swx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5vt00swx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:layout-solid" /></template>
