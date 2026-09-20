<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sljaq7bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sljaq7bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hackerone" /></template>
