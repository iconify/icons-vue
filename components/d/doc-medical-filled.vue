<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0oj0k_rf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r0oj0k_rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:doc-medical-filled" /></template>
