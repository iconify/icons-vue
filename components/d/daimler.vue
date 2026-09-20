<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uixl3td8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uixl3td8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:daimler" /></template>
