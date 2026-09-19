<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd0c7ccwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rd0c7ccwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:hashtag-20-solid" /></template>
