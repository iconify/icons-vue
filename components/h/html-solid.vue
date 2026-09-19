<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn1nskbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn1nskbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:html-solid" /></template>
