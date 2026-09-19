<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apk1qtb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="apk1qtb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-rm" /></template>
