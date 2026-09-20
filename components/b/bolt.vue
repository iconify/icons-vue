<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wao7fvqjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wao7fvqjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:bolt" /></template>
