<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psv6wg5ow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psv6wg5ow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:download" /></template>
