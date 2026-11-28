<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao_ermbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao_ermbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-image-check" /></template>
