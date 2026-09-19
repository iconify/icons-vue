<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br71gpb8p.css';
import '../../css/i/izu9akmqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="br71gpb8p"/><rect class="izu9akmqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:clipboard-outline" /></template>
