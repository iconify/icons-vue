<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mstr9jbxl.css';
import '../../css/d/dtz_ylbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer mstr9jbxl"/><path class="dtz_ylbin duoicon-secondary-layer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:bug" /></template>
