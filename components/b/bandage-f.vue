<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pghgizbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1,"top":-1};
const content = `<path class="pghgizbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:bandage-f" /></template>
