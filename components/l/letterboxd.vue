<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6l2v_wvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o6l2v_wvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:letterboxd" /></template>
