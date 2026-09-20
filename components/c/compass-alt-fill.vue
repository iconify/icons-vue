<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar2gvbdfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ar2gvbdfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:compass-alt-fill" /></template>
