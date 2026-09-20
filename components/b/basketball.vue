<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frjbdm0tp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="frjbdm0tp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:basketball" /></template>
