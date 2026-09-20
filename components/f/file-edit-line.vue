<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_mg4ui-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_mg4ui-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-edit-line" /></template>
