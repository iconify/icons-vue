<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oduvyo18i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oduvyo18i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:jpeg-logo-block" /></template>
