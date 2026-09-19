<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyfafeb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyfafeb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-long-left" /></template>
