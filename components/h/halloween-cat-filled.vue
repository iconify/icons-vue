<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdmsjpzen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xdmsjpzen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:halloween-cat-filled" /></template>
