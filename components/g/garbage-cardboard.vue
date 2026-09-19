<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivck_9bxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivck_9bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:garbage-cardboard" /></template>
