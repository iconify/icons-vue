<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovn9bfb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovn9bfb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:info-line" /></template>
