<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3m0kabdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a3m0kabdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:lock-open" /></template>
