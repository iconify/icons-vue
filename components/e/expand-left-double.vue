<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na29cjd5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na29cjd5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:expand-left-double" /></template>
