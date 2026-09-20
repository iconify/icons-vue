<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw5a_8jwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw5a_8jwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ever" /></template>
