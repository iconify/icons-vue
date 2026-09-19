<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrdy0obbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrdy0obbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:command-solid" /></template>
