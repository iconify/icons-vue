<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qapbn_but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qapbn_but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:carrefour" /></template>
