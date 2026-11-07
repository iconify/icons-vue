<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dff8bp7ci.css';
import '../../css/g/gpwxw0bmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dff8bp7ci"/><path class="gpwxw0bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dialog-2-bold" /></template>
