<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs8r0wbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs8r0wbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:delete" /></template>
