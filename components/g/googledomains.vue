<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyr3f_b8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyr3f_b8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:googledomains" /></template>
