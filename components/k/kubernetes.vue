<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi4d1ebgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="yi4d1ebgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:kubernetes" /></template>
