<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2wv6_umn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z2wv6_umn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:admin" /></template>
