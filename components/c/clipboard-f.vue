<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_ifm87jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="d_ifm87jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:clipboard-f" /></template>
