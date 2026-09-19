<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sii5elbef.css';
import '../../css/v/vdb-37byt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sii5elbef"/><path clip-rule="evenodd" class="vdb-37byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:book-outline" /></template>
