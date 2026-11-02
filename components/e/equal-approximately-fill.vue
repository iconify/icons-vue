<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvdqtuhcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvdqtuhcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:equal-approximately-fill" /></template>
