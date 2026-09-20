<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekpb2hbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekpb2hbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:brightness" /></template>
