<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm4ts6b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hm4ts6b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:folder" /></template>
