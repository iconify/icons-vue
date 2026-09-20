<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c58wlsbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c58wlsbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:html5" /></template>
