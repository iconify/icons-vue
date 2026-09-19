<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anhm5qwyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anhm5qwyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:award-outline" /></template>
