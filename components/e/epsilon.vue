<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu_-1daos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu_-1daos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:epsilon" /></template>
