<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o20vhit8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o20vhit8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:file-minus-filled" /></template>
