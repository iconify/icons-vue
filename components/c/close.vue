<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oul7wv0ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-6,"top":-6};
const content = `<path class="oul7wv0ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:close" /></template>
