<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p15-u2b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p15-u2b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:keycdn" /></template>
