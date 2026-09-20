<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9978lb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9978lb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:alfaromeo" /></template>
