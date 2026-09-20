<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b09a7qbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b09a7qbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ana" /></template>
