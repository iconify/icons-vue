<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltt-bqb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltt-bqb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:laravel-solid" /></template>
