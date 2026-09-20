<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcibe0bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcibe0bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:comment-solid" /></template>
