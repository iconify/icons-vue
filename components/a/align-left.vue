<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6xus7bkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6xus7bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-left" /></template>
