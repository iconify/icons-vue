<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz00br_eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pz00br_eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:folder-files-filled" /></template>
