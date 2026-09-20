<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6jgq8r9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6jgq8r9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:jmpt" /></template>
