<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl_okblxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl_okblxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:gusto" /></template>
