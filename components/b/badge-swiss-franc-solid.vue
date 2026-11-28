<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y25geurdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y25geurdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:badge-swiss-franc-solid" /></template>
