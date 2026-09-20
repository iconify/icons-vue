<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkzr2r9mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nkzr2r9mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:eye-off-filled" /></template>
