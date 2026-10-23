<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2u71zzfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2u71zzfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-plus" /></template>
