<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot4vp4spt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ot4vp4spt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:layout-alt-01-filled" /></template>
