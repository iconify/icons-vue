<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfw-zbcoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfw-zbcoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:kununu" /></template>
