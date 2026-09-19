<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6br34_0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a6br34_0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:cpanel" /></template>
