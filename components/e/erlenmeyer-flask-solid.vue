<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypgz2tbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ypgz2tbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:erlenmeyer-flask-solid" /></template>
