<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6brtmb2k.css';
import '../../css/p/p-2h8ebhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6brtmb2k"/><path class="p-2h8ebhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:download-alt" /></template>
