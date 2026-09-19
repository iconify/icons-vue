<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yypen4wvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yypen4wvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:announcement-filled" /></template>
