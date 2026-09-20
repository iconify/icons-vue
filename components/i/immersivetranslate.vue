<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/darj4dbtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="darj4dbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:immersivetranslate" /></template>
