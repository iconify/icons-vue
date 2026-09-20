<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn4a9db6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<path class="pn4a9db6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:bell-off" /></template>
