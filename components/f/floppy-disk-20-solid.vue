<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y551u-61r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="y551u-61r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:floppy-disk-20-solid" /></template>
