<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euf698iox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="euf698iox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-moon-hail" /></template>
