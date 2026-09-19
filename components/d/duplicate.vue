<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls7z-wykt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls7z-wykt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:duplicate" /></template>
