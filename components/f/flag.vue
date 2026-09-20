<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-cnb6b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-cnb6b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:flag" /></template>
