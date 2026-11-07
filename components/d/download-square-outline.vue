<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6ah1yb_u.css';
import '../../css/u/u9tzwj7ok.css';
import '../../css/m/mzfoi9l1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6ah1yb_u"/><path class="u9tzwj7ok"/><path clip-rule="evenodd" class="mzfoi9l1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:download-square-outline" /></template>
