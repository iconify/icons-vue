<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp5ots5-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gp5ots5-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:align-bottom" /></template>
