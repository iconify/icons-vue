<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af3qo4aum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af3qo4aum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-zip" /></template>
