<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b03u49keo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b03u49keo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:globe-plus" /></template>
