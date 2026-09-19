<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5l-vby2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5l-vby2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:file-system-outlined" /></template>
