<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzby9lbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dzby9lbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bill2" /></template>
