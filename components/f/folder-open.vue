<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc-nwqgsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="pc-nwqgsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:folder-open" /></template>
