<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7kb0dbiu.css';
import '../../css/o/o5jloubyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7kb0dbiu"/><path class="o5jloubyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-safety-filled" /></template>
