<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3hdh9k9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g3hdh9k9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-path-single-counterclockwise-solid" /></template>
