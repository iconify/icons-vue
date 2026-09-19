<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr9lctgvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vr9lctgvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:fedora" /></template>
