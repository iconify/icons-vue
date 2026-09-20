<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esmtatn3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esmtatn3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dropbox-line" /></template>
