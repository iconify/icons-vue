<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie91gw6sh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ie91gw6sh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-link" /></template>
