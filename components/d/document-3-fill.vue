<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cacy0409r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cacy0409r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:document-3-fill" /></template>
