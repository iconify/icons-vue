<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9l-hbbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9l-hbbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:citrix" /></template>
