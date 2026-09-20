<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivclsta8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivclsta8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:grid-edit-filled" /></template>
