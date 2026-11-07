<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/movjw89ew.css';
import '../../css/a/ax9g9_14z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="movjw89ew"/><path class="ax9g9_14z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:login-bold" /></template>
