<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsm9vtg9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsm9vtg9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heart-solid" /></template>
