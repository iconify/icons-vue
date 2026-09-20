<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv5e8ydir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv5e8ydir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cross-filled" /></template>
