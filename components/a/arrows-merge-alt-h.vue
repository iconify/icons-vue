<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxw5baccr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxw5baccr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrows-merge-alt-h" /></template>
