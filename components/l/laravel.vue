<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b09m9nbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b09m9nbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:laravel" /></template>
