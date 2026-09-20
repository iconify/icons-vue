<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui4p003tf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="ui4p003tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:close-rectangle-f" /></template>
