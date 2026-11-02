<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2my29ccn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2my29ccn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ethereum-fill" /></template>
