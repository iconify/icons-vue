<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xph2au4ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xph2au4ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:element" /></template>
