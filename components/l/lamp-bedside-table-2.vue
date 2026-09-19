<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciswazb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ciswazb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lamp-bedside-table-2" /></template>
