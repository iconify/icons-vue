<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akni7yb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akni7yb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dlna" /></template>
