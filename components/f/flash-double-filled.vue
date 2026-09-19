<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqol4wbub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wqol4wbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:flash-double-filled" /></template>
