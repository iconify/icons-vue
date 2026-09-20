<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w313eccov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w313eccov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:lock-password-open-filled" /></template>
