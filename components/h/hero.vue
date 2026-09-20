<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc-o5ilbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oc-o5ilbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hero" /></template>
