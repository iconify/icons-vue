<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6599-3lv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6599-3lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:drop1" /></template>
