<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmg9y89jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmg9y89jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:file-scan-filled" /></template>
