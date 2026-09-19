<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_7p9s-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":771,"height":1024};
const content = `<path class="nz_7p9s-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:kohana" /></template>
