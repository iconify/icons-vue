<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr8bbzbli.css';
import '../../css/l/lo4g9ospx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cr8bbzbli"/><path class="lo4g9ospx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cake-filled" /></template>
