<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdbvcv8lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-7};
const content = `<path class="cdbvcv8lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:fish" /></template>
