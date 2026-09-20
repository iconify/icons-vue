<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdz_qi1ok.css';
import '../../css/m/mwyoejbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdz_qi1ok"/><path clip-rule="evenodd" class="mwyoejbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lit" /></template>
