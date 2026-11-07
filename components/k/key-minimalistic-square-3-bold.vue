<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8qfwibcp.css';
import '../../css/l/lnqwqtb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8qfwibcp"/><path clip-rule="evenodd" class="lnqwqtb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:key-minimalistic-square-3-bold" /></template>
