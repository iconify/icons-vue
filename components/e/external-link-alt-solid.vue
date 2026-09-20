<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_-acu8zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a_-acu8zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:external-link-alt-solid" /></template>
