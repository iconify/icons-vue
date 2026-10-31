<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycy3tlwgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycy3tlwgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:folder-open-gloss" /></template>
