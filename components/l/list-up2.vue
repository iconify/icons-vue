<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7tqw4a7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l7tqw4a7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:list-up2" /></template>
