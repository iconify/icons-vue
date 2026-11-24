<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beh5j7yso.css';
import '../../css/g/ggxl3abdx.css';
import '../../css/v/vgshsqbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="beh5j7yso"/><path class="ggxl3abdx"/><path class="vgshsqbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-letter-p-off-filled" /></template>
