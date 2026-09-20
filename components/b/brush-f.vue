<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkr7lxyrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-3.5};
const content = `<path class="fkr7lxyrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:brush-f" /></template>
