<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjriywbzo.css';
import '../../css/a/acxc33bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mjriywbzo"/><path class="acxc33bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:copy-x-filled" /></template>
