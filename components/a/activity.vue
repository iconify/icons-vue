<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9sh5i22h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-3};
const content = `<path class="j9sh5i22h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:activity" /></template>
