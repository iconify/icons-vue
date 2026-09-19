<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt2b-sb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt2b-sb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:google-drive-solid" /></template>
