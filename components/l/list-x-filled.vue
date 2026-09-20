<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi3jvebpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qi3jvebpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:list-x-filled" /></template>
