<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2gdeacls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2gdeacls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clipboard-typography-filled" /></template>
