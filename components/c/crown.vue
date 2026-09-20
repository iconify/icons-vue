<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az7xd_bwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="az7xd_bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:crown" /></template>
