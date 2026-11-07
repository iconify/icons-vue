<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s28m-k17m.css';
import '../../css/p/p9comhf0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s28m-k17m"/><path clip-rule="evenodd" class="p9comhf0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-down-minimalistic-outline" /></template>
