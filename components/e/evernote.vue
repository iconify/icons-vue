<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exv5f0b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":488};
const content = `<path class="exv5f0b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:evernote" /></template>
