<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvhwkcbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pvhwkcbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:delete-2-solid" /></template>
