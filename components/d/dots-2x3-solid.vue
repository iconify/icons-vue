<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j855_w7iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j855_w7iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-2x3-solid" /></template>
