<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngtu_95cw.css';
import '../../css/f/fqk5odb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngtu_95cw"/><path class="fqk5odb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:ball" /></template>
