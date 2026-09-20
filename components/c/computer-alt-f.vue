<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozb5jvb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="ozb5jvb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:computer-alt-f" /></template>
