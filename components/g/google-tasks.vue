<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h10vm2bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h10vm2bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:google-tasks" /></template>
