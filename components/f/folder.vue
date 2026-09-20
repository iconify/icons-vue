<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krg18ob7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krg18ob7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:folder" /></template>
