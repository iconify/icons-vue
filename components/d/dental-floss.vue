<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm0apjj5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xm0apjj5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:dental-floss" /></template>
