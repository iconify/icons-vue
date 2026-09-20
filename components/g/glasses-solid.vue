<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc33sp-io.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc33sp-io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:glasses-solid" /></template>
