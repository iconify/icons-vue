<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyq4nf5rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyq4nf5rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:libreoffice-math" /></template>
