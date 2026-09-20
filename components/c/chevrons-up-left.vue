<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgq__9z0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-5};
const content = `<path class="qgq__9z0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevrons-up-left" /></template>
