<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmu6wq9zl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gmu6wq9zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:clipboard-list" /></template>
