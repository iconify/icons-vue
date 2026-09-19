<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_2isublj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x_2isublj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:bitbucket" /></template>
