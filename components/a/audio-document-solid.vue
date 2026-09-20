<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gljxhwefi.css';
import '../../css/l/lus1dsb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gljxhwefi"/><path clip-rule="evenodd" class="lus1dsb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:audio-document-solid" /></template>
