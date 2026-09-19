<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmnevccbt.css';
import '../../css/v/vzdhx2clg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zmnevccbt"/><path class="vzdhx2clg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-folder-open" /></template>
