<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2srsomua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g2srsomua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:lens-concave" /></template>
