<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkf9rhutl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hkf9rhutl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bonfire" /></template>
