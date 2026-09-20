<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgo5q3yca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wgo5q3yca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:lock-keyhole-filled" /></template>
