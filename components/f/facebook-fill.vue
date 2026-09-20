<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7x7htp7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="f7x7htp7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:facebook-fill" /></template>
