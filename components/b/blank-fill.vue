<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgv2w6bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vgv2w6bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:blank-fill" /></template>
