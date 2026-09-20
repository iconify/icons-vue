<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad72w3bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="ad72w3bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:envelope-f" /></template>
