<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks18lwb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ks18lwb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-woff2-small-filled" /></template>
