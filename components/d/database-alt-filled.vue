<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov3qt0kxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ov3qt0kxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:database-alt-filled" /></template>
