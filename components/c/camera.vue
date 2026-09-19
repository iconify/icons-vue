<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrh9vbbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrh9vbbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:camera" /></template>
