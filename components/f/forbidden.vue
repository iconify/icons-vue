<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwz2z7_7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lwz2z7_7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:forbidden" /></template>
