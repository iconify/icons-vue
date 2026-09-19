<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tttity4uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tttity4uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-down-left-square-solid" /></template>
