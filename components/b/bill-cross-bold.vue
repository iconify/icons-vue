<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dug55mbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dug55mbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bill-cross-bold" /></template>
