<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oarzgyboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oarzgyboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:label-off" /></template>
