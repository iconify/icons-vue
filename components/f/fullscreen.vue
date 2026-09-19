<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or_nacp9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="or_nacp9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:fullscreen" /></template>
