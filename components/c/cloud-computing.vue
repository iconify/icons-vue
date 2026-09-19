<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-j7aeb6e.css';
import '../../css/o/oy2n5ob-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-j7aeb6e"/><path class="oy2n5ob-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:cloud-computing" /></template>
