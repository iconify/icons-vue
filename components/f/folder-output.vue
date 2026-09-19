<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-io-bc4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-io-bc4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-output" /></template>
