<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of5hlmbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of5hlmbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:folder-remove" /></template>
