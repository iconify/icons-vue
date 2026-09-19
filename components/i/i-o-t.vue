<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iar3svb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="iar3svb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:i-o-t" /></template>
