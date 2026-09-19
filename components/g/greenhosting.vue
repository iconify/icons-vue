<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bons_pz5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="bons_pz5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:greenhosting" /></template>
