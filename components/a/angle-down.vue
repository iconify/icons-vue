<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8b8npfbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8b8npfbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:angle-down" /></template>
