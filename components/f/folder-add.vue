<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl4404x2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xl4404x2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-add" /></template>
