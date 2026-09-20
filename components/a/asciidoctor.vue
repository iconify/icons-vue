<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c27hrob2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c27hrob2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:asciidoctor" /></template>
