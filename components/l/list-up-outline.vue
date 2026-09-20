<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmkb8jbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jmkb8jbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-up-outline" /></template>
