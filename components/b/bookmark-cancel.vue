<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6gwcblpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t6gwcblpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bookmark-cancel" /></template>
