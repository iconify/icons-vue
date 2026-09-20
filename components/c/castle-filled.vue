<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz3n_jqgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xz3n_jqgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:castle-filled" /></template>
