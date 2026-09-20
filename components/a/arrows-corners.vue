<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_t0jac-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="o_t0jac-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:arrows-corners" /></template>
