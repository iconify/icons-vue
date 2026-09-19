<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ist_axrux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="ist_axrux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:file-video" /></template>
