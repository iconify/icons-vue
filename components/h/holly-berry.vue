<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz-e9hbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fz-e9hbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:holly-berry" /></template>
