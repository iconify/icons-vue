<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-jtknb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x-jtknb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:hospital-fill" /></template>
