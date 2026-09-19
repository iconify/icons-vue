<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1llemb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="o1llemb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:location-north-fill" /></template>
