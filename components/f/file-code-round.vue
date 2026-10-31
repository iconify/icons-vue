<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2o510z7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2o510z7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-code-round" /></template>
