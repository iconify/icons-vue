<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkoy5f77i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nkoy5f77i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:archive-document" /></template>
