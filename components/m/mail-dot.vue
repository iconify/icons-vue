<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltua8abtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltua8abtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-dot" /></template>
