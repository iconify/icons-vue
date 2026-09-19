<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1w3o7btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n1w3o7btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:caret-down-solid" /></template>
