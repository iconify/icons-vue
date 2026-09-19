<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lani2cc-y.css';
import '../../css/m/maksvyb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lani2cc-y"/><path class="maksvyb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-docker" /></template>
