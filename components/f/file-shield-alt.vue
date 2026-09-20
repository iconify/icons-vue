<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1p4y9t4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1p4y9t4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-shield-alt" /></template>
