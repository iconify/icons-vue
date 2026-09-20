<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh-6nid-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh-6nid-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:fluentd" /></template>
