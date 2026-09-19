<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw01wvbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pw01wvbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:fire-off-filled" /></template>
