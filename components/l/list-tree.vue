<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uakhfck7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uakhfck7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:list-tree" /></template>
