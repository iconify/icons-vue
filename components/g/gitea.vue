<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-h908znd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n-h908znd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:gitea" /></template>
