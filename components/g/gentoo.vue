<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgfij9bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="zgfij9bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:gentoo" /></template>
