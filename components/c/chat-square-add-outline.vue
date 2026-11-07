<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npl5ovbfu.css';
import '../../css/u/um_zvyb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npl5ovbfu"/><path clip-rule="evenodd" class="um_zvyb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-add-outline" /></template>
