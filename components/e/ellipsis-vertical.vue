<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/j/ja7twxd8s.css';
import '../../css/j/jxl67pbry.css';
import '../../css/d/d2xz6hb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="ja7twxd8s"/><circle class="jxl67pbry"/><circle class="d2xz6hb5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:ellipsis-vertical" /></template>
