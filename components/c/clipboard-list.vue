<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsohqs5pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsohqs5pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:clipboard-list" /></template>
