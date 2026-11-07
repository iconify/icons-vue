<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmi9_q11s.css';
import '../../css/x/x446f-znb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmi9_q11s"/><path clip-rule="evenodd" class="x446f-znb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-edit-bold" /></template>
