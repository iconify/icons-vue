<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfk6dpb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfk6dpb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:denon" /></template>
