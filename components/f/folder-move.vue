<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj___ac1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sj___ac1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-move" /></template>
