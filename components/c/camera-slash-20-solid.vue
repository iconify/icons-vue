<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6lx4hq4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="n6lx4hq4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:camera-slash-20-solid" /></template>
