<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kweki9fds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kweki9fds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:graphcool" /></template>
