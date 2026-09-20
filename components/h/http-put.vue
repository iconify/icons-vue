<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsq2kbeni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsq2kbeni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:http-put" /></template>
