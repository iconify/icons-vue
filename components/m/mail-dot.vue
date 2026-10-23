<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de8u3vrlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de8u3vrlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mail-dot" /></template>
