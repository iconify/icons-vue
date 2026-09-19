<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grmnn1biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":544,"height":472};
const content = `<path class="grmnn1biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:image" /></template>
