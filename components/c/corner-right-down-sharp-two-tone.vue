<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py_7xmyxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py_7xmyxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:corner-right-down-sharp-two-tone" /></template>
