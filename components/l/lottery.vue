<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szr8xwb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="szr8xwb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:lottery" /></template>
