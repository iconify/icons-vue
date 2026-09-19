<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knf8ffp_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":503,"height":512};
const content = `<path class="knf8ffp_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:dylib" /></template>
