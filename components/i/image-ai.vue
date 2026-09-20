<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf46vybxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf46vybxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:image-ai" /></template>
