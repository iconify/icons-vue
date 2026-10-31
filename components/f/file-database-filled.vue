<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-cm0ty8h.css';
import '../../css/u/uwwux4bdl.css';
import '../../css/l/l_fae7rzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i-cm0ty8h"/><path class="uwwux4bdl"/><path class="l_fae7rzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-database-filled" /></template>
