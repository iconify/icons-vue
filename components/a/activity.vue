<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aton4b70c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aton4b70c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:activity" /></template>
