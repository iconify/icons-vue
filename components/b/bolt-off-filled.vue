<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dibn1jbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dibn1jbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bolt-off-filled" /></template>
