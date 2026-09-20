<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnfi_dhky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnfi_dhky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-p-small" /></template>
