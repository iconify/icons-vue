<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2v5tnvzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2v5tnvzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:facebook-circle-fill" /></template>
